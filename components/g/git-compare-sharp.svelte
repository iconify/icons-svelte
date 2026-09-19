<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd8as1mpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fd8as1mpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:git-compare-sharp" {...props}></Icon>
