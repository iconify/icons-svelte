<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bexblibhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bexblibhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:bar-chart" {...props}></Icon>
