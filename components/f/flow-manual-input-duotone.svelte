<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh7d4-wmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zh7d4-wmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-manual-input-duotone" {...props}></Icon>
