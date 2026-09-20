<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psx67-bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="psx67-bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-vertical-right" {...props}></Icon>
