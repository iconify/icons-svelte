<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4-6d7bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4-6d7bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-off" {...props}></Icon>
