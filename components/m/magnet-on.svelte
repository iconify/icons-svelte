<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxr9j-bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxr9j-bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magnet-on" {...props}></Icon>
