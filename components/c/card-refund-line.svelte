<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mji4-fs_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mji4-fs_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:card-refund-line" {...props}></Icon>
