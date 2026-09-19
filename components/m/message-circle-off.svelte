<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmxt7qbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmxt7qbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-circle-off" {...props}></Icon>
