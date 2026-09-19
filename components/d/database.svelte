<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2f-umren.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g2f-umren"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:database" {...props}></Icon>
