<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjozsnoyg.css';
import '../../css/q/qwzgryv0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjozsnoyg"/><path class="qwzgryv0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-snow-line" {...props}></Icon>
