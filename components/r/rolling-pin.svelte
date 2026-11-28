<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx9cgwk4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx9cgwk4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rolling-pin" {...props}></Icon>
