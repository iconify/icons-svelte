<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpvc8lxor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpvc8lxor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:list-music-solid" {...props}></Icon>
