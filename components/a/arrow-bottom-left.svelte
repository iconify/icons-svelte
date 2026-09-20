<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yau_oxycf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yau_oxycf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:arrow-bottom-left" {...props}></Icon>
