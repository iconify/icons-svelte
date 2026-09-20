<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tate_tblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tate_tblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-filled" {...props}></Icon>
