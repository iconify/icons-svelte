<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg5k18buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rg5k18buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-up-16-solid" {...props}></Icon>
