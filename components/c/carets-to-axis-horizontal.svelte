<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbswtxmxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbswtxmxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:carets-to-axis-horizontal" {...props}></Icon>
