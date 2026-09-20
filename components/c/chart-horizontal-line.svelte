<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojnu-8dvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojnu-8dvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-horizontal-line" {...props}></Icon>
