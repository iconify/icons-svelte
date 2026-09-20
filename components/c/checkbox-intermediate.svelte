<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb-qxl-bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb-qxl-bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-intermediate" {...props}></Icon>
