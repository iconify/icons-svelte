<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn4b-obfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn4b-obfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bot-x" {...props}></Icon>
