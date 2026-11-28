<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9tt2uonp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9tt2uonp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:filter-x" {...props}></Icon>
