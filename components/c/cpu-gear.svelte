<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmpinr99k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmpinr99k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cpu-gear" {...props}></Icon>
