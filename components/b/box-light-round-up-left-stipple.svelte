<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gee286b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gee286b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-up-left-stipple" {...props}></Icon>
