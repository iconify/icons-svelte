<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db0ssxsmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db0ssxsmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:forbid-circle-line" {...props}></Icon>
