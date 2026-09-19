<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3x9-strl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3x9-strl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-left-05" {...props}></Icon>
