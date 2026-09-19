<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zodqo1c7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zodqo1c7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:reddit" {...props}></Icon>
