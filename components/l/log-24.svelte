<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smod414ny.css';
import '../../css/o/ol4ckq3wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smod414ny"/><path class="ol4ckq3wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:log-24" {...props}></Icon>
