<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx74kcluf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx74kcluf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:briefcase-outline" {...props}></Icon>
