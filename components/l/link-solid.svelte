<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqf92tbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqf92tbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:link-solid" {...props}></Icon>
