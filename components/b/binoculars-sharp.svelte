<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji6d9equt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ji6d9equt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:binoculars-sharp" {...props}></Icon>
