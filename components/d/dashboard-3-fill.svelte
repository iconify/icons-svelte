<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2vd5wbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2vd5wbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dashboard-3-fill" {...props}></Icon>
