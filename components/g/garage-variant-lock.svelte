<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9qnd8fgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9qnd8fgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:garage-variant-lock" {...props}></Icon>
