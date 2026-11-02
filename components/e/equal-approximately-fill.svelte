<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvdqtuhcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvdqtuhcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:equal-approximately-fill" {...props}></Icon>
