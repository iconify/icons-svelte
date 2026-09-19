<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsew7abve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsew7abve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:power-panel-logo" {...props}></Icon>
