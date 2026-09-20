<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llk6ldgmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llk6ldgmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-bookmark" {...props}></Icon>
