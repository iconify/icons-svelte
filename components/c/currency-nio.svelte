<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol7eugljr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol7eugljr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-nio" {...props}></Icon>
