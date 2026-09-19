<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fob5qsb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fob5qsb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:power-20-solid" {...props}></Icon>
