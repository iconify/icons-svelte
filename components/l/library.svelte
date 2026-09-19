<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5shn-vfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i5shn-vfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:library" {...props}></Icon>
