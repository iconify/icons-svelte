<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb5z5zncd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rb5z5zncd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chartbrew" {...props}></Icon>
