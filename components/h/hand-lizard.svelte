<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueziy6bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ueziy6bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:hand-lizard" {...props}></Icon>
