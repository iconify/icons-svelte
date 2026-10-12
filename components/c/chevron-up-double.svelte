<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg7s-p90e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg7s-p90e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chevron-up-double" {...props}></Icon>
