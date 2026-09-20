<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhnqpabwu.css';
import '../../css/d/d2kvgvbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":375,"height":375};
const content = `<defs><path id="SVGdOj2Ibak" class="nhnqpabwu"/></defs><use href="#SVGdOj2Ibak" class="d2kvgvbvc"/><use href="#SVGdOj2Ibak" class="d2kvgvbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:glincker" {...props}></Icon>
