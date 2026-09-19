<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spat6qbum.css';
import '../../css/g/ga5ow5xim.css';
import '../../css/x/x8r3bo3uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="spat6qbum"/><path class="ga5ow5xim"/><path class="x8r3bo3uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-pak-business-automation" {...props}></Icon>
