<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v328shbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v328shbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:card-stack" {...props}></Icon>
