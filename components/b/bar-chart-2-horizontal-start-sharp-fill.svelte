<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbn3k0brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbn3k0brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-2-horizontal-start-sharp-fill" {...props}></Icon>
