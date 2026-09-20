<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm9149b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm9149b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baseball-2-line" {...props}></Icon>
