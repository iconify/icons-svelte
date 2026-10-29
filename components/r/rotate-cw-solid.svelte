<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ribff0qeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ribff0qeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rotate-cw-solid" {...props}></Icon>
