<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k55i2mb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k55i2mb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:order-play-line" {...props}></Icon>
