<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifn16dbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ifn16dbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-split" {...props}></Icon>
