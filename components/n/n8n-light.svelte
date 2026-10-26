<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxeetebtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":96};
const content = `<path class="gxeetebtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:n8n-light" {...props}></Icon>
