<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ep0gb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m4ep0gb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-bar-chart-2-horizontal-start-fill" {...props}></Icon>
