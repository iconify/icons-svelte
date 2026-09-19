<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij_azbbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ij_azbbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:egg-solid" {...props}></Icon>
