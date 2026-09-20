<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c885x9kbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c885x9kbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-s-fill" {...props}></Icon>
