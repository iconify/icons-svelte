<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2wcqfbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":640};
const content = `<path class="c2wcqfbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:capacitator" {...props}></Icon>
