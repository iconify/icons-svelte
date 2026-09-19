<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz7kf-lsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xz7kf-lsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bars-progress" {...props}></Icon>
