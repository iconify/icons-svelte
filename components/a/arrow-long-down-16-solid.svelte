<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjlwf8m8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vjlwf8m8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-long-down-16-solid" {...props}></Icon>
