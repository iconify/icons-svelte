<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzgw9y50r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzgw9y50r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:filter-sort-filled" {...props}></Icon>
