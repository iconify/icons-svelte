<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6vdgmb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6vdgmb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-x-line" {...props}></Icon>
