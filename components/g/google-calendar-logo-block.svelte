<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok93i9baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ok93i9baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-calendar-logo-block" {...props}></Icon>
