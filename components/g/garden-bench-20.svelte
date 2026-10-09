<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfdw6bbqs.css';
import '../../css/k/kpsjv5nug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nfdw6bbqs"/><path class="kpsjv5nug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:garden-bench-20" {...props}></Icon>
