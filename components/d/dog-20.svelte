<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2s5ueg_q.css';
import '../../css/v/vm8t9uryo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w2s5ueg_q"/><path class="vm8t9uryo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dog-20" {...props}></Icon>
