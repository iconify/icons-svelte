<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr4xlubum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qr4xlubum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:hoppscotch" {...props}></Icon>
