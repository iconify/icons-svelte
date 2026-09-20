<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elx6aybyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="elx6aybyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:braille-blind" {...props}></Icon>
