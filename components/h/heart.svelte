<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq1q7fzgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mq1q7fzgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:heart" {...props}></Icon>
