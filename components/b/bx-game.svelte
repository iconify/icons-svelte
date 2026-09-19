<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg0h8xb-u.css';
import '../../css/c/c0keyp4fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg0h8xb-u"/><circle class="c0keyp4fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-game" {...props}></Icon>
