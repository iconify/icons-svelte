<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smu97hcnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="smu97hcnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:quill" {...props}></Icon>
