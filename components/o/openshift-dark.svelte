<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdh71-7os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdh71-7os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openshift-dark" {...props}></Icon>
