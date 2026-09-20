<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz9t6ee6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz9t6ee6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:plurk" {...props}></Icon>
