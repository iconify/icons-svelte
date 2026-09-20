<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii1rvbbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ii1rvbbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:latin-cross" {...props}></Icon>
