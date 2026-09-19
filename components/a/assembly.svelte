<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbfi7hipm.css';
import '../../css/a/amdrwrbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="jbfi7hipm"/><path class="amdrwrbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:assembly" {...props}></Icon>
