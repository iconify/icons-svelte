<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n53m4vbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n53m4vbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-space-around" {...props}></Icon>
