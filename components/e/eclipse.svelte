<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nux1njbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nux1njbpd"><animateTransform attributeName="transform" dur="0.6s" repeatCount="indefinite" type="rotate" values="0 12 12;360 12 12"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="svg-spinners:eclipse" {...props}></Icon>
