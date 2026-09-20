<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-0lfcb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="q-0lfcb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-both-direction-vertical-1" {...props}></Icon>
