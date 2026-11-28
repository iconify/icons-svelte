<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rixc3yb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rixc3yb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:printer-gear" {...props}></Icon>
