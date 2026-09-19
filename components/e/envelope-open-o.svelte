<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmr9r7v8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="jmr9r7v8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:envelope-open-o" {...props}></Icon>
