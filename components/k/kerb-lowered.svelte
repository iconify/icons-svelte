<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmt67jnfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hmt67jnfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:kerb-lowered" {...props}></Icon>
