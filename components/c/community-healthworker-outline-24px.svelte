<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l97ph9b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l97ph9b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:community-healthworker-outline-24px" {...props}></Icon>
