<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kajys0kmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kajys0kmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-oval-left-16-solid" {...props}></Icon>
