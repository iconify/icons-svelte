<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df0h_ihsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df0h_ihsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flame-filled" {...props}></Icon>
