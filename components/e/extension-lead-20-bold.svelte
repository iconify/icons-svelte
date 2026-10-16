<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqyen_7is.css';
import '../../css/c/cj85dubro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lqyen_7is"/><path class="cj85dubro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:extension-lead-20-bold" {...props}></Icon>
