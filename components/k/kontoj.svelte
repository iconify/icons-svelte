<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agda5ibxs.css';
import '../../css/d/dp3eanaee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="agda5ibxs"/><path class="dp3eanaee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kontoj" {...props}></Icon>
