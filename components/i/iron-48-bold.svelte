<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo0h7bcsg.css';
import '../../css/r/rh51rxbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vo0h7bcsg"/><path class="rh51rxbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:iron-48-bold" {...props}></Icon>
