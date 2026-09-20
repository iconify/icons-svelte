<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3fse_b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r3fse_b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:enter" {...props}></Icon>
