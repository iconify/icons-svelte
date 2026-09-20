<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo-rlxbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uo-rlxbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:chevron-left" {...props}></Icon>
