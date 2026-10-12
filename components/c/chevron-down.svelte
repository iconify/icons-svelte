<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyu6-1wma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyu6-1wma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chevron-down" {...props}></Icon>
