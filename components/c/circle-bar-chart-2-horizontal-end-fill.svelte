<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2u4hqven.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x2u4hqven"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-bar-chart-2-horizontal-end-fill" {...props}></Icon>
