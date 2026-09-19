<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntry6-bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ntry6-bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:package" {...props}></Icon>
