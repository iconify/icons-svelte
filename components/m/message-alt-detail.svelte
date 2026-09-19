<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah_u9vljd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah_u9vljd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-alt-detail" {...props}></Icon>
