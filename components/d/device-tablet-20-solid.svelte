<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5lxrlnwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w5lxrlnwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:device-tablet-20-solid" {...props}></Icon>
