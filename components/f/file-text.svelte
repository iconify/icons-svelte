<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkpcixbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tkpcixbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:file-text" {...props}></Icon>
