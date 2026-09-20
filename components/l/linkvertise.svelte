<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnar4sbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnar4sbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:linkvertise" {...props}></Icon>
