<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0gym56-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p0gym56-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pencil-square-solid" {...props}></Icon>
