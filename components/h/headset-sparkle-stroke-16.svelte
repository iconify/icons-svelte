<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyjlmrb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qyjlmrb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:headset-sparkle-stroke-16" {...props}></Icon>
