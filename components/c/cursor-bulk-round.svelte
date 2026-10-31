<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgtx0hbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgtx0hbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cursor-bulk-round" {...props}></Icon>
