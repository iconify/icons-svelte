<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsr0t4_oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsr0t4_oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:crunchyrol" {...props}></Icon>
