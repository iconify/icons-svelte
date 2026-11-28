<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2komvbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary w2komvbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:qr-code-duotone" {...props}></Icon>
