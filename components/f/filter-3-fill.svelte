<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrm94cbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrm94cbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:filter-3-fill" {...props}></Icon>
