<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja9mf_b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ja9mf_b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:placard" {...props}></Icon>
