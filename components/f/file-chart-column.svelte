<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o28emeehs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o28emeehs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-chart-column" {...props}></Icon>
