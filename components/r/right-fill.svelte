<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtxr2ky9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtxr2ky9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:right-fill" {...props}></Icon>
