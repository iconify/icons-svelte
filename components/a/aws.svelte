<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8sowac7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":480};
const content = `<path class="q8sowac7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:aws" {...props}></Icon>
