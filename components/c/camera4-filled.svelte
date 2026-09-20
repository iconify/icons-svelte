<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa3_i26zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa3_i26zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera4-filled" {...props}></Icon>
