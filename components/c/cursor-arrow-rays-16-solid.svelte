<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra2ozbcib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ra2ozbcib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cursor-arrow-rays-16-solid" {...props}></Icon>
