<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxta4n_om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gxta4n_om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-in-box-gabled-shelter" {...props}></Icon>
