<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw74ukb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw74ukb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-image" {...props}></Icon>
