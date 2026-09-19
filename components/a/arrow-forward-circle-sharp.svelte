<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccmeg2w-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ccmeg2w-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-forward-circle-sharp" {...props}></Icon>
