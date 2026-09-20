<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx17bi-cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx17bi-cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-reverse-large-fill" {...props}></Icon>
