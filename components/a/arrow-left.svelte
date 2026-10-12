<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um1iiosha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um1iiosha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-left" {...props}></Icon>
