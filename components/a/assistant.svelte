<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4l3g20lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="n4l3g20lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:assistant" {...props}></Icon>
