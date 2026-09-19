<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3lm1rjzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3lm1rjzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:microsoft-infopath" {...props}></Icon>
