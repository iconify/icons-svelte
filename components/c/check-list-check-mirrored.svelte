<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6ncrbthp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i6ncrbthp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:check-list-check-mirrored" {...props}></Icon>
