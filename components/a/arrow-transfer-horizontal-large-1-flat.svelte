<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd69qcbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sd69qcbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-transfer-horizontal-large-1-flat" {...props}></Icon>
