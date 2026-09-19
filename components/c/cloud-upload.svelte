<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrm53eszd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrm53eszd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-upload" {...props}></Icon>
