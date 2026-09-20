<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ful1m9b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ful1m9b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:camera" {...props}></Icon>
