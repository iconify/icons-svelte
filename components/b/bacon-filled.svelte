<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5g9zdbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5g9zdbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bacon-filled" {...props}></Icon>
