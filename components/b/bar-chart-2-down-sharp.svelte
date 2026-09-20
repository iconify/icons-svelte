<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a932zqezp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a932zqezp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-2-down-sharp" {...props}></Icon>
