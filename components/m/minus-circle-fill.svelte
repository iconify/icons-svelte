<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huxi8-spp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="huxi8-spp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:minus-circle-fill" {...props}></Icon>
