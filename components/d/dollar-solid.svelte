<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd34weaop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hd34weaop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:dollar-solid" {...props}></Icon>
