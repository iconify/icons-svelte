<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asb-_0zbx.css';
import '../../css/m/m37_gnbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asb-_0zbx"/><path class="m37_gnbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-log-out-circle" {...props}></Icon>
