<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au9_58mke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="au9_58mke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:increase-indent-text-mirrored" {...props}></Icon>
