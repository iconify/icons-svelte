<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbfu52bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jbfu52bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-rr" {...props}></Icon>
