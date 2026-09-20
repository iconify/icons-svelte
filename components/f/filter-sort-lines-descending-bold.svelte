<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc06x8qpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc06x8qpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:filter-sort-lines-descending-bold" {...props}></Icon>
