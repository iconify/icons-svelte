<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q35elrbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q35elrbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bed-solid" {...props}></Icon>
