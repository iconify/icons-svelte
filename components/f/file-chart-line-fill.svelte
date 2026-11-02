<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayk_p8mde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayk_p8mde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-chart-line-fill" {...props}></Icon>
