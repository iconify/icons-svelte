<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuf02xbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tuf02xbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-amex" {...props}></Icon>
