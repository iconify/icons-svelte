<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k__xz2kbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k__xz2kbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:at-line" {...props}></Icon>
