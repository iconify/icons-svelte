<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt3r6j27x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kt3r6j27x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:multiline-fill-16" {...props}></Icon>
