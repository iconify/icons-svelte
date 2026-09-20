<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6tua-b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6tua-b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bar-chart-fill" {...props}></Icon>
