<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofkr7ob2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ofkr7ob2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bookmark-dash-fill" {...props}></Icon>
