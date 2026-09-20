<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srzis3ldt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="srzis3ldt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:memorial-stone-with-quaker-star" {...props}></Icon>
