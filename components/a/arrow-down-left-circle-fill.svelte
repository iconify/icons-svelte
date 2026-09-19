<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr7h7gujd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gr7h7gujd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-left-circle-fill" {...props}></Icon>
