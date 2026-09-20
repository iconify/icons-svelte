<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v250d_hni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v250d_hni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:hospital-15" {...props}></Icon>
