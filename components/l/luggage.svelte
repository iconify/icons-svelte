<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7765vlsl.css';
import '../../css/q/q51k3abci.css';
import '../../css/k/ke4xsybbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7765vlsl wm-k"/><path class="q51k3abci wm-k"/><path class="ke4xsybbc wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:luggage" {...props}></Icon>
