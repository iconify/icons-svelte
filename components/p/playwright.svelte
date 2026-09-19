<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fouy3m4oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fouy3m4oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:playwright" {...props}></Icon>
