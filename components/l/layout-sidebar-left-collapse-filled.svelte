<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prn9v0brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prn9v0brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-sidebar-left-collapse-filled" {...props}></Icon>
