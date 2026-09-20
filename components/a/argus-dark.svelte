<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8b8zrjqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8b8zrjqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:argus-dark" {...props}></Icon>
