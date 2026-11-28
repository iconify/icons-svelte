<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcpvd8l-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcpvd8l-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-down-left" {...props}></Icon>
