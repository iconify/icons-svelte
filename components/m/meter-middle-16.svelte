<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6ima4-rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t6ima4-rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:meter-middle-16" {...props}></Icon>
