<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg_w6jmdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg_w6jmdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lidl" {...props}></Icon>
