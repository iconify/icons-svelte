<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehv5ztb4q.css';
import '../../css/i/ijrr7tsvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ehv5ztb4q"/><path class="ijrr7tsvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-left-down-20-bold" {...props}></Icon>
