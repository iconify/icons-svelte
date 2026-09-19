<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtufp_f3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtufp_f3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-big-left-filled" {...props}></Icon>
