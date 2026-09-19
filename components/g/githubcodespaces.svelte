<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjry_ebno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tjry_ebno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:githubcodespaces" {...props}></Icon>
