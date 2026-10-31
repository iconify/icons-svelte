<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhemmwbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nhemmwbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:quotation-mark-16-solid" {...props}></Icon>
