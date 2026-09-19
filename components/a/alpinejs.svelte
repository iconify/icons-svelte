<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-11jrk6e.css';
import '../../css/z/zx7fs7byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="j-11jrk6e"/><path clip-rule="evenodd" class="zx7fs7byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:alpinejs" {...props}></Icon>
