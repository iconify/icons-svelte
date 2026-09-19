<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmn9y9neh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dmn9y9neh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:git-commit" {...props}></Icon>
