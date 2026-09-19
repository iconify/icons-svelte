<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujzt-9bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ujzt-9bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:megaphone-16-solid" {...props}></Icon>
