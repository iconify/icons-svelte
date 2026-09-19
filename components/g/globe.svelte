<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chj9ap-la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="chj9ap-la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:globe" {...props}></Icon>
