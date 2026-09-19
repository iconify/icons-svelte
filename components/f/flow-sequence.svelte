<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8yn8gg6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j8yn8gg6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow-sequence" {...props}></Icon>
