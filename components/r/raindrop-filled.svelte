<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex6zhjb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex6zhjb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:raindrop-filled" {...props}></Icon>
