<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-kukhd7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":488};
const content = `<path class="g-kukhd7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:google" {...props}></Icon>
