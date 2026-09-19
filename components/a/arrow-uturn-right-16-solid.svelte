<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw_9so7zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sw_9so7zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-right-16-solid" {...props}></Icon>
