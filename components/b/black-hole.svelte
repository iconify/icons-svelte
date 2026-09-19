<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_uftmr9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e_uftmr9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:black-hole" {...props}></Icon>
