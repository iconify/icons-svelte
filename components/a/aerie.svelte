<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v18hzdb8f.css';
import '../../css/d/d0u33jbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="v18hzdb8f"/><path class="d0u33jbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aerie" {...props}></Icon>
