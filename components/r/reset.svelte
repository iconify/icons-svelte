<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne2sisi1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ne2sisi1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:reset" {...props}></Icon>
