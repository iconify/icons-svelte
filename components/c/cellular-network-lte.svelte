<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lax5n35xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lax5n35xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cellular-network-lte" {...props}></Icon>
