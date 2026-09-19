<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzrmc7i5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mzrmc7i5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-slash-outline" {...props}></Icon>
