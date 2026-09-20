<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3-25i8ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3-25i8ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alert-circle-check-outline" {...props}></Icon>
