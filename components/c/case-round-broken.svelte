<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k8q120b9o.css';
import '../../css/f/fh0zq9b-s.css';
import '../../css/m/m4w84s94u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k8q120b9o"/><path class="fh0zq9b-s"/><path class="m4w84s94u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-round-broken" {...props}></Icon>
