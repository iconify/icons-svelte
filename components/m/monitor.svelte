<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps5vdrchl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps5vdrchl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:monitor" {...props}></Icon>
