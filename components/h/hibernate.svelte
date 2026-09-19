<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdtmj-bqy.css';
import '../../css/n/nlvvtjrbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vdtmj-bqy"/><path class="nlvvtjrbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:hibernate" {...props}></Icon>
