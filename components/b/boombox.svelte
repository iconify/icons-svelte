<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oztf66rsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="oztf66rsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:boombox" {...props}></Icon>
