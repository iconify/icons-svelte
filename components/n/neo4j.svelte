<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vse78tblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":459,"height":512};
const content = `<path class="vse78tblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:neo4j" {...props}></Icon>
