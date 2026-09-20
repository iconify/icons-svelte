<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eow2v3j8v.css';
import '../../css/l/lylvmeb0j.css';
import '../../css/c/cgm5haclf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eow2v3j8v"/><path class="lylvmeb0j"/><path class="cgm5haclf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chorizard-light" {...props}></Icon>
