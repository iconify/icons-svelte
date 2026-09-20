<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_p2kezbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_p2kezbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:call-off-filled" {...props}></Icon>
