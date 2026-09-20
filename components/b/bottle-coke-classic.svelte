<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7h2f57dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7h2f57dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bottle-coke-classic" {...props}></Icon>
