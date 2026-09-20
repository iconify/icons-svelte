<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtg3-_bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtg3-_bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:hospital-symbol" {...props}></Icon>
