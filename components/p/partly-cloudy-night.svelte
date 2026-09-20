<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwlv0fbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="qwlv0fbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:partly-cloudy-night" {...props}></Icon>
