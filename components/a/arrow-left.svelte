<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n--fw0uon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n--fw0uon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:arrow-left" {...props}></Icon>
