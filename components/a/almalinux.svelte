<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6sbetbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g6sbetbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:almalinux" {...props}></Icon>
