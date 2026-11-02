<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awc4shbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awc4shbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:case-upper-line" {...props}></Icon>
