<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5kx7i42m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5kx7i42m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:backspace-thin" {...props}></Icon>
