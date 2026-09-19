<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbw0r8mbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbw0r8mbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:bar-chart" {...props}></Icon>
