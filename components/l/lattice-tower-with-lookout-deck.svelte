<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ectx9jbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ectx9jbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lattice-tower-with-lookout-deck" {...props}></Icon>
