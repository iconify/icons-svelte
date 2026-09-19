<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiddfub6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiddfub6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bar-chart-square-filled" {...props}></Icon>
