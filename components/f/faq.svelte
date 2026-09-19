<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4_6p9oov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="u4_6p9oov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:faq" {...props}></Icon>
