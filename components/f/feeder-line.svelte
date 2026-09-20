<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkkysdgde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkkysdgde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:feeder-line" {...props}></Icon>
