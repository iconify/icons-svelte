<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhxx82bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhxx82bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device" {...props}></Icon>
