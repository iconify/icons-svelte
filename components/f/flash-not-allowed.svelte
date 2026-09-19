<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no7dq_bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no7dq_bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:flash-not-allowed" {...props}></Icon>
