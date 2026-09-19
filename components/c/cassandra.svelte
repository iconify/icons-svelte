<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po7r85g_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="po7r85g_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cassandra" {...props}></Icon>
