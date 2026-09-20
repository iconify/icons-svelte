<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx4lt75ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx4lt75ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bird" {...props}></Icon>
