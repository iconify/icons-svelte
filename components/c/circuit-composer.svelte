<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhvfzxc8c.css';
import '../../css/k/km4pjabfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rhvfzxc8c"/><path class="km4pjabfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:circuit-composer" {...props}></Icon>
