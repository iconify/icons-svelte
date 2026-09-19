<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx7kf_b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vx7kf_b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-powerpoint" {...props}></Icon>
