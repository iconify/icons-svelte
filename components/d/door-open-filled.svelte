<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll2pwacuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll2pwacuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:door-open-filled" {...props}></Icon>
