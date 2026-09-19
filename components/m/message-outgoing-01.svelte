<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxmfpebgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxmfpebgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-outgoing-01" {...props}></Icon>
