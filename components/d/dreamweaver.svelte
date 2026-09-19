<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l20foz2hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l20foz2hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:dreamweaver" {...props}></Icon>
