<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1middb0q.css';
import '../../css/o/o42c9jpgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1middb0q"/><path class="o42c9jpgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dishwasher-20" {...props}></Icon>
