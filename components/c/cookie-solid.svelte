<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpmyr_clo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpmyr_clo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cookie-solid" {...props}></Icon>
