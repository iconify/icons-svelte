<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw8p30bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw8p30bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-up-right-double-fill" {...props}></Icon>
