<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6cff_bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n6cff_bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apacheignite" {...props}></Icon>
