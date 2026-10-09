<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqsj93biv.css';
import '../../css/u/uwl5ht5rg.css';
import '../../css/d/d0igczcjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wqsj93biv"/><path class="uwl5ht5rg"/><path class="d0igczcjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-alert-20-bold" {...props}></Icon>
