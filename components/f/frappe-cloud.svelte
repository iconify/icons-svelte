<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4_kwrboz.css';
import '../../css/o/oa0cpabtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d4_kwrboz"/><path class="oa0cpabtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-cloud" {...props}></Icon>
