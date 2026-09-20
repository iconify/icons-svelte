<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hey_i9tsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hey_i9tsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-refresh" {...props}></Icon>
