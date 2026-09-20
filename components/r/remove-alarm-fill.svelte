<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiqiw5b2f.css';
import '../../css/w/wz4v0s-qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiqiw5b2f"/><path clip-rule="evenodd" class="wz4v0s-qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:remove-alarm-fill" {...props}></Icon>
