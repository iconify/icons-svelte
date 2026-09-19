<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvsppfdxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tvsppfdxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cup" {...props}></Icon>
