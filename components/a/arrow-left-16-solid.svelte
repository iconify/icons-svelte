<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0jek1b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r0jek1b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-left-16-solid" {...props}></Icon>
