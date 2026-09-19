<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m44z8bb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m44z8bb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:alert" {...props}></Icon>
