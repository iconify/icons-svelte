<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frg06o3hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="frg06o3hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-left-to-line" {...props}></Icon>
