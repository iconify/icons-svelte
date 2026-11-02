<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e50bn5bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e50bn5bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:invite-fill" {...props}></Icon>
