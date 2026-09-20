<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a726jb9_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a726jb9_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:radio-on" {...props}></Icon>
