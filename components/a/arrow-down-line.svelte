<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnx-q8bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnx-q8bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-down-line" {...props}></Icon>
