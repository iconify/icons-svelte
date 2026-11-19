<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njuxs6bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njuxs6bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:move-vertical" {...props}></Icon>
