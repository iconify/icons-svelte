<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wslbe0b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wslbe0b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrange-send-backward" {...props}></Icon>
