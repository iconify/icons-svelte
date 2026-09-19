<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n39z9fd7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n39z9fd7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:overcast" {...props}></Icon>
