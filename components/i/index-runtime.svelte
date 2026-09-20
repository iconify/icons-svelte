<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyo412_1k.css';
import '../../css/l/l40lmxbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eyo412_1k"/><path class="l40lmxbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:index-runtime" {...props}></Icon>
