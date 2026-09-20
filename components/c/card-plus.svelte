<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syg-rq9ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syg-rq9ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-plus" {...props}></Icon>
