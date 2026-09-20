<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e41sh2w3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":394};
const content = `<path class="e41sh2w3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:blitz" {...props}></Icon>
