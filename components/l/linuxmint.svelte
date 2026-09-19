<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6b-ou0ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m6b-ou0ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:linuxmint" {...props}></Icon>
