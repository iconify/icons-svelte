<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdlufeb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jdlufeb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-left-circle-16-solid" {...props}></Icon>
