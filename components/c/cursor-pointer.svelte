<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7w8o9bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i7w8o9bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cursor-pointer" {...props}></Icon>
