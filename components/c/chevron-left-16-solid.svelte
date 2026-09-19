<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv68uobyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gv68uobyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-left-16-solid" {...props}></Icon>
