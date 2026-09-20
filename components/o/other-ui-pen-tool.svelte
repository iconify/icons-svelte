<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh_25h19d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wh_25h19d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-pen-tool" {...props}></Icon>
