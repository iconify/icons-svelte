<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brladpbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":560,"height":730};
const content = `<path class="brladpbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:emphasis" {...props}></Icon>
