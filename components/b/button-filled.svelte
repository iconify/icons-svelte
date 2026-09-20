<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1xmxc0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1xmxc0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:button-filled" {...props}></Icon>
