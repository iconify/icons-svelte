<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mudz3pbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mudz3pbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hotkey-line" {...props}></Icon>
