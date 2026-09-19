<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fina31b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fina31b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:atom" {...props}></Icon>
