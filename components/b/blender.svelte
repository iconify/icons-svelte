<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agnn5lbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="agnn5lbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:blender" {...props}></Icon>
