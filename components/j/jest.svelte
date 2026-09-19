<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5gs9tbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a5gs9tbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jest" {...props}></Icon>
