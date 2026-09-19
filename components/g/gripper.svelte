<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1gfipb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z1gfipb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:gripper" {...props}></Icon>
