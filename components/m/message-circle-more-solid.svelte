<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqr1_2k-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqr1_2k-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-more-solid" {...props}></Icon>
