<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcpac4h9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcpac4h9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pinia" {...props}></Icon>
