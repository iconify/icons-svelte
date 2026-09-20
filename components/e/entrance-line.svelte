<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgzard9se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgzard9se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:entrance-line" {...props}></Icon>
