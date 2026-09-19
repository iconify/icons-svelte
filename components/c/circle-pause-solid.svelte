<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq7wl2-2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uq7wl2-2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:circle-pause-solid" {...props}></Icon>
