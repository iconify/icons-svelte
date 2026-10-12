<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijq1e5-qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijq1e5-qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrows-horizontal" {...props}></Icon>
