<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oanleacgm.css';
import '../../css/o/opsmh7beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oanleacgm"/><path class="opsmh7beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:delete" {...props}></Icon>
