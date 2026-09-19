<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx3a9x_sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fx3a9x_sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-discover" {...props}></Icon>
