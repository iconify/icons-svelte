<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqnb87bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqnb87bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrows-up" {...props}></Icon>
