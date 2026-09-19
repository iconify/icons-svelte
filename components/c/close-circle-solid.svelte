<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxji21-fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uxji21-fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:close-circle-solid" {...props}></Icon>
