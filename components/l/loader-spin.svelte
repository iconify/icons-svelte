<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/dlu5--u4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><animateTransform attributeName="transform" dur="1s" from="0 12 12" repeatCount="indefinite" to="360 12 12" type="rotate"/><path class="dlu5--u4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:loader-spin" {...props}></Icon>
