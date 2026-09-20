<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhu9g0z5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhu9g0z5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mailbox-open-up-outline" {...props}></Icon>
