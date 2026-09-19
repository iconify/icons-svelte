<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hla5t0g8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hla5t0g8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:ifixit" {...props}></Icon>
