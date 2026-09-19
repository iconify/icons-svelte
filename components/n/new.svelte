<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akajx_bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akajx_bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:new" {...props}></Icon>
