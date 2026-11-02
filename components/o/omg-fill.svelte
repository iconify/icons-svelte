<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joubnnbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="joubnnbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:omg-fill" {...props}></Icon>
