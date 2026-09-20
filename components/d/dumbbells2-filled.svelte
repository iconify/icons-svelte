<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xizp-3d-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xizp-3d-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:dumbbells2-filled" {...props}></Icon>
