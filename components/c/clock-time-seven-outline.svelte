<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z72316buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z72316buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-seven-outline" {...props}></Icon>
