<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbc0g8wzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cbc0g8wzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-16-solid" {...props}></Icon>
