<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cukjm2ikv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cukjm2ikv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:letter-case-capitalize" {...props}></Icon>
