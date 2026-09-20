<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc0ef1bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uc0ef1bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:magnifying-glass" {...props}></Icon>
