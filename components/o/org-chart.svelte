<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vat9n5byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vat9n5byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:org-chart" {...props}></Icon>
