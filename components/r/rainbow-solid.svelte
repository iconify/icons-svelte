<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm_avmgbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm_avmgbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rainbow-solid" {...props}></Icon>
