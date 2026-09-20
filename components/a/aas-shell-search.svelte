<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bikw38bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bikw38bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell-search" {...props}></Icon>
