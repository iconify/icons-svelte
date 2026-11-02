<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/horck1bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="horck1bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:nintendo-switch-fill" {...props}></Icon>
