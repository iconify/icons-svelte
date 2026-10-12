<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucpbrwyid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucpbrwyid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:grip-vertical" {...props}></Icon>
