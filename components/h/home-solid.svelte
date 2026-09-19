<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r89r5fl9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r89r5fl9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:home-solid" {...props}></Icon>
