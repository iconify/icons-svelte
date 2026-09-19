<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fay30qbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":24};
const content = `<path class="fay30qbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bluetooth-b" {...props}></Icon>
