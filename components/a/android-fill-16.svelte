<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0b7glbxa.css';
import '../../css/z/zyv9ekbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b0b7glbxa"/><path class="zyv9ekbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:android-fill-16" {...props}></Icon>
