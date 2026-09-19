<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3he7ubvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i3he7ubvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cloud-arrow-up-16-solid" {...props}></Icon>
