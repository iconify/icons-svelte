<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebky43byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="ebky43byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fblike" {...props}></Icon>
