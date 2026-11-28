<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcp2szuyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcp2szuyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-arrow-right" {...props}></Icon>
