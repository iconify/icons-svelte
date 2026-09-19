<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3utyhbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3utyhbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:door-filled" {...props}></Icon>
