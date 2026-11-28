<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lls-5vwgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lls-5vwgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:receipt-edit" {...props}></Icon>
