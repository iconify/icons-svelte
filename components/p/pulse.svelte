<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdnqjebwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle r="0" class="vdnqjebwm"><animate attributeName="r" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" repeatCount="indefinite" values="0;11"/><animate attributeName="opacity" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" repeatCount="indefinite" values="1;0"/></circle>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="svg-spinners:pulse" {...props}></Icon>
