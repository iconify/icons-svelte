<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyhvu77cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyhvu77cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dropdown-filled" {...props}></Icon>
