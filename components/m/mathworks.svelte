<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8877ob4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s8877ob4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mathworks" {...props}></Icon>
