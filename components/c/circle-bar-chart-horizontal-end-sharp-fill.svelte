<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx2t-v_0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rx2t-v_0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-bar-chart-horizontal-end-sharp-fill" {...props}></Icon>
