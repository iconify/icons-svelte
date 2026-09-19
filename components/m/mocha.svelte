<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_d9xbc-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d_d9xbc-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:mocha" {...props}></Icon>
