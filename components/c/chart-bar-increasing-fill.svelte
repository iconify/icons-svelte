<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc3b0korc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc3b0korc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-increasing-fill" {...props}></Icon>
