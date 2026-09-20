<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmdn2ybsd.css';
import '../../css/r/rnvgnfbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pmdn2ybsd"/><path clip-rule="evenodd" class="rnvgnfbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:file-text-16" {...props}></Icon>
