<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcbrlmb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcbrlmb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:corner-up-right-outline" {...props}></Icon>
