<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2dnefb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q2dnefb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:exit" {...props}></Icon>
