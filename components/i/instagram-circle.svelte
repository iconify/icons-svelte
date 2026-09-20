<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cickl6b4l.css';
import '../../css/i/i8f6vsb_g.css';
import '../../css/n/n8gcj1byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cickl6b4l"/><path class="i8f6vsb_g"/><path class="n8gcj1byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:instagram-circle" {...props}></Icon>
