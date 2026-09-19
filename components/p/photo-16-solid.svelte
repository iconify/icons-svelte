<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npuhqsm5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="npuhqsm5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:photo-16-solid" {...props}></Icon>
