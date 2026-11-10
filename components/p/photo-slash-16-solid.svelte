<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etdfqxe4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="etdfqxe4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-slash-16-solid" {...props}></Icon>
