<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpoi46r1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bpoi46r1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:menu-dots-16" {...props}></Icon>
