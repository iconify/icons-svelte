<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s305xebir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s305xebir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-minus-fill" {...props}></Icon>
