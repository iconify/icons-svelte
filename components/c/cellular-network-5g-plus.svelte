<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s82ukkblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s82ukkblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cellular-network-5g-plus" {...props}></Icon>
