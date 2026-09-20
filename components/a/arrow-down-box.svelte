<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk10_ekef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mk10_ekef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-down-box" {...props}></Icon>
