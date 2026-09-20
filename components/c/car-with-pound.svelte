<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oquz19bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oquz19bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-pound" {...props}></Icon>
