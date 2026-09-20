<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu0q_f7sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu0q_f7sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-automotive" {...props}></Icon>
