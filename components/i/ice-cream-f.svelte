<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4xm48b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="g4xm48b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:ice-cream-f" {...props}></Icon>
