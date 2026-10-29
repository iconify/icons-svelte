<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lep7-fbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lep7-fbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:badge-check-solid" {...props}></Icon>
