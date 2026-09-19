<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7v4vubya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m7v4vubya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:osi" {...props}></Icon>
