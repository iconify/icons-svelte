<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfoza2ewb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfoza2ewb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-bottom-line" {...props}></Icon>
