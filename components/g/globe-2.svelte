<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw3eezbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cw3eezbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:globe-2" {...props}></Icon>
