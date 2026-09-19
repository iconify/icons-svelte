<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0dxmwn6y.css';
import '../../css/h/h6dm1v_wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0dxmwn6y"/><path class="h6dm1v_wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:close" {...props}></Icon>
