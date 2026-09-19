<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l84ftsbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l84ftsbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:decision-node" {...props}></Icon>
