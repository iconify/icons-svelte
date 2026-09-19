<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh_8zbb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh_8zbb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:map-pin-alt-solid" {...props}></Icon>
