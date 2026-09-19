<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs-bohb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vs-bohb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:google-solid" {...props}></Icon>
