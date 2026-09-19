<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph9q5h07s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ph9q5h07s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:capslock" {...props}></Icon>
