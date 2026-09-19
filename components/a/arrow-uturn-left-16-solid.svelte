<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhh6njb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vhh6njb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-left-16-solid" {...props}></Icon>
