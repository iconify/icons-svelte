<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6h96-z2f.css';
import '../../css/z/zj49idy7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6h96-z2f"/><path class="zj49idy7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:plus-circle-24" {...props}></Icon>
