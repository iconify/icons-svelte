<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os0nxpbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os0nxpbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:line" {...props}></Icon>
