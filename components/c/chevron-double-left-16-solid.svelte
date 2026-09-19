<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4ytt9oqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a4ytt9oqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-left-16-solid" {...props}></Icon>
