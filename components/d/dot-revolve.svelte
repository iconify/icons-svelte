<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnis27-yq.css';
import '../../css/l/l7-dtibrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnis27-yq"/><circle class="l7-dtibrc"><animateTransform attributeName="transform" dur="0.75s" repeatCount="indefinite" type="rotate" values="0 12 12;360 12 12"/></circle>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="svg-spinners:dot-revolve" {...props}></Icon>
