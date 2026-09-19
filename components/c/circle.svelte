<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad2u7zbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ad2u7zbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:circle" {...props}></Icon>
