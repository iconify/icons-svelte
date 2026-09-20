<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo28neb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xo28neb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-bar-chart-horizontal-start-sharp-fill" {...props}></Icon>
