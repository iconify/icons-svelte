<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8l_9bbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8l_9bbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-woman-solid" {...props}></Icon>
