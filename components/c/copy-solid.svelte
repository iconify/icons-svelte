<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_5tsvbed.css';
import '../../css/l/ls7yfwb3e.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 u_5tsvbed"/><rect class="clr-i-solid clr-i-solid-path-2 ls7yfwb3e"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:copy-solid" {...props}></Icon>
