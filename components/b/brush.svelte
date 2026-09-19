<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iea4lyb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iea4lyb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:brush" {...props}></Icon>
