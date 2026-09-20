<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-xkov5aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="o-xkov5aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-stipple-right" {...props}></Icon>
