<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4c5z7bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m4c5z7bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:mysql" {...props}></Icon>
