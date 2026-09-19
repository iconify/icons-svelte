<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj0r58dgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj0r58dgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:instagram-solid" {...props}></Icon>
