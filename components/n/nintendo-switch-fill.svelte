<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbyr-ac6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbyr-ac6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:nintendo-switch-fill" {...props}></Icon>
