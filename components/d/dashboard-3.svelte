<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe14brbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xe14brbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dashboard-3" {...props}></Icon>
