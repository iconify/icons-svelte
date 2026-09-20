<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9-x1ja6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9-x1ja6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:crosshair-plus" {...props}></Icon>
