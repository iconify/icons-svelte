<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-2grmbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-2grmbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:four-wheel-drive-fill" {...props}></Icon>
