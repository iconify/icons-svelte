<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlg_xcbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlg_xcbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:download" {...props}></Icon>
