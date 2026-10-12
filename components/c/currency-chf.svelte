<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxdycwq-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxdycwq-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-chf" {...props}></Icon>
