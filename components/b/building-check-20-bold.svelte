<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqsj93biv.css';
import '../../css/u/uwl5ht5rg.css';
import '../../css/q/qvksvzdwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wqsj93biv"/><path class="uwl5ht5rg"/><path class="qvksvzdwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-check-20-bold" {...props}></Icon>
