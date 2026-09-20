<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f23g89byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f23g89byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cursor-hand" {...props}></Icon>
