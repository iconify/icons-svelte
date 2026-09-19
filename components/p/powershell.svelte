<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-xf7lbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="u-xf7lbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:powershell" {...props}></Icon>
