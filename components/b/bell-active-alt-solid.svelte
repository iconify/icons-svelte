<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4gq_zbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4gq_zbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bell-active-alt-solid" {...props}></Icon>
