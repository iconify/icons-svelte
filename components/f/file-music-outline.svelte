<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtc4babzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtc4babzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-music-outline" {...props}></Icon>
