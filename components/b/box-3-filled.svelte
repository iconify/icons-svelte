<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs4pb60ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs4pb60ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:box-3-filled" {...props}></Icon>
