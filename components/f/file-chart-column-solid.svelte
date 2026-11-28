<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkq-xq00b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkq-xq00b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-chart-column-solid" {...props}></Icon>
