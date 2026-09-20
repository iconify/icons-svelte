<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krjyr2bou.css';
import '../../css/e/e9nqe7b2h.css';
import '../../css/k/k8ixw89dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="krjyr2bou"/><path class="e9nqe7b2h"/><path class="k8ixw89dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:articles-rtl" {...props}></Icon>
