<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxqj9naah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pxqj9naah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:packer" {...props}></Icon>
