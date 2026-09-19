<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdq0fiufx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdq0fiufx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:phone-hangup-outline" {...props}></Icon>
