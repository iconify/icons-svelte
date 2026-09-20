<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxy9z3b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cxy9z3b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:calc" {...props}></Icon>
