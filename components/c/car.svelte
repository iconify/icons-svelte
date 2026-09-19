<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyor_thbf.css';
import '../../css/p/psi0ttbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<circle class="oyor_thbf"/><path class="psi0ttbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:car" {...props}></Icon>
