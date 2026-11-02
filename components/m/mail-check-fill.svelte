<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnznm6t1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnznm6t1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-check-fill" {...props}></Icon>
