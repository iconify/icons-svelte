<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb2g502qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb2g502qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-big-right-solid" {...props}></Icon>
