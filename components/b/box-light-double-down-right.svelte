<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csjoy6p0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="csjoy6p0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-down-right" {...props}></Icon>
