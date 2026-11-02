<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixk8e1a3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixk8e1a3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dice-4-fill" {...props}></Icon>
