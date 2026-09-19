<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_32zi80z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_32zi80z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:caret-forward-outline" {...props}></Icon>
