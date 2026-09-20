<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcpry4u-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcpry4u-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clock-circle-bold" {...props}></Icon>
