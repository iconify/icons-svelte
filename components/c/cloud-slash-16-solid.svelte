<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzwn0bbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lzwn0bbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-slash-16-solid" {...props}></Icon>
