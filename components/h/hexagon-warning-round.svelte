<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbz1xnpzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbz1xnpzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-warning-round" {...props}></Icon>
