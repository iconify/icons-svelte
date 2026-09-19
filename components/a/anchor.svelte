<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv4di9b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mv4di9b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:anchor" {...props}></Icon>
