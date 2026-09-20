<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am8x09bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am8x09bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-add" {...props}></Icon>
