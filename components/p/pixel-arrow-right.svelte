<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp0hb84pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zp0hb84pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-arrow-right" {...props}></Icon>
