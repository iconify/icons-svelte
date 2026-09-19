<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxye8sb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jxye8sb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:eye-dropper-16-solid" {...props}></Icon>
