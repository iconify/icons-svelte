<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujrt7accy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ujrt7accy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jinja" {...props}></Icon>
