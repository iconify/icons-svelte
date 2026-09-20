<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/big0egopn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="big0egopn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bag-plus-outline" {...props}></Icon>
