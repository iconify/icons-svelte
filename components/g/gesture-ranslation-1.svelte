<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3g4u7q3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3g4u7q3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-ranslation-1" {...props}></Icon>
