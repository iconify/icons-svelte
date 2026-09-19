<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m53y9kbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m53y9kbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:layers-outline" {...props}></Icon>
