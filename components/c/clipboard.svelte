<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl2mnppab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="xl2mnppab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:clipboard" {...props}></Icon>
