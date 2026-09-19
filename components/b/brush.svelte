<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-h7_1-zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b-h7_1-zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:brush" {...props}></Icon>
