<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpsm8ob7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpsm8ob7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cfx" {...props}></Icon>
