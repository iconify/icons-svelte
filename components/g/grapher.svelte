<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt1rccc2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":487,"height":512};
const content = `<path class="dt1rccc2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:grapher" {...props}></Icon>
