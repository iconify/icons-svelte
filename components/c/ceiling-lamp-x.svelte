<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbvgft8xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbvgft8xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ceiling-lamp-x" {...props}></Icon>
