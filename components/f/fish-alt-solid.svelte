<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylx_4ubcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylx_4ubcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:fish-alt-solid" {...props}></Icon>
