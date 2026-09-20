<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojnzdfbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojnzdfbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-4k-filled" {...props}></Icon>
