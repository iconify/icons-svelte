<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibdbo8z7t.css';
import '../../css/w/w9i8zcc7s.css';
import '../../css/d/dt9g5gbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ibdbo8z7t"/><path class="w9i8zcc7s"/><path class="dt9g5gbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:imaging-alternative-mri-two" {...props}></Icon>
