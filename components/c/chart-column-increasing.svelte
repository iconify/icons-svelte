<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt4jk-xcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt4jk-xcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-column-increasing" {...props}></Icon>
