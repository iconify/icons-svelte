<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcw1qbpct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcw1qbpct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-plus-solid" {...props}></Icon>
