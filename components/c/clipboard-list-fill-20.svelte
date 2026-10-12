<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlwaf4b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xlwaf4b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-list-fill-20" {...props}></Icon>
