<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aslg49b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aslg49b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:natural-arch" {...props}></Icon>
