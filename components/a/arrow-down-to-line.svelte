<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxr-nkffo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xxr-nkffo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-down-to-line" {...props}></Icon>
