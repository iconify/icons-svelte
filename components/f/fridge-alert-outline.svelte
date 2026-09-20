<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjx9z_bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjx9z_bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-alert-outline" {...props}></Icon>
