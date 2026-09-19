<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z63w88byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="z63w88byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pytest" {...props}></Icon>
