<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsp2g4brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsp2g4brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:basketball-round" {...props}></Icon>
