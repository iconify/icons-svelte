<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi-8yhbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gi-8yhbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:octagon-20" {...props}></Icon>
