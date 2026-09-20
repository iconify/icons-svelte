<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-34oac9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-34oac9y"><animateTransform attributeName="transform" dur="0.75s" repeatCount="indefinite" type="rotate" values="0 12 12;360 12 12"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="svg-spinners:90-ring" {...props}></Icon>
