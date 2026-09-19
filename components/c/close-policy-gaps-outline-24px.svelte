<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvv7_nbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvv7_nbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:close-policy-gaps-outline-24px" {...props}></Icon>
