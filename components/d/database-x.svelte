<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r190aubtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r190aubtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:database-x" {...props}></Icon>
