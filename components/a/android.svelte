<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgob4pbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mgob4pbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:android" {...props}></Icon>
