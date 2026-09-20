<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocs2_-bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocs2_-bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:blur-off" {...props}></Icon>
