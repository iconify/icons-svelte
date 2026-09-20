<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nho5m3r6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nho5m3r6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive-check" {...props}></Icon>
