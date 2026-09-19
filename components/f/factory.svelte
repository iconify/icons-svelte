<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtzvfs7nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gtzvfs7nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:factory" {...props}></Icon>
