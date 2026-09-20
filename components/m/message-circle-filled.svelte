<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox8shz4bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox8shz4bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-filled" {...props}></Icon>
