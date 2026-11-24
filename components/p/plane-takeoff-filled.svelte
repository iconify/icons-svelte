<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-c_p0b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-c_p0b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:plane-takeoff-filled" {...props}></Icon>
