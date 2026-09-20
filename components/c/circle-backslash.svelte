<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2c55hbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q2c55hbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:circle-backslash" {...props}></Icon>
