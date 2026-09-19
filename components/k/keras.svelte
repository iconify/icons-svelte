<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxy-htbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nxy-htbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:keras" {...props}></Icon>
