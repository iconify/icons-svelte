<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olpxcdbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="olpxcdbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:fortran" {...props}></Icon>
