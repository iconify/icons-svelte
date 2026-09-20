<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9h0xjb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="e9h0xjb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:partly-cloudy-day" {...props}></Icon>
