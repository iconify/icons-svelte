<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uct1ooplc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uct1ooplc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:resize" {...props}></Icon>
