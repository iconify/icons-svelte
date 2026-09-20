<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usw10sb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usw10sb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell-filled" {...props}></Icon>
