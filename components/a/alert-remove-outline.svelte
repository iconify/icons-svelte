<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcb-l8b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcb-l8b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alert-remove-outline" {...props}></Icon>
