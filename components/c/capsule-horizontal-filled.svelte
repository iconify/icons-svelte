<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqku5tbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqku5tbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:capsule-horizontal-filled" {...props}></Icon>
