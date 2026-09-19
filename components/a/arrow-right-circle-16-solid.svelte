<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwqiqrk0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rwqiqrk0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-circle-16-solid" {...props}></Icon>
