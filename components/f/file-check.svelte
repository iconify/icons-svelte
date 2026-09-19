<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7rnv2w-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j7rnv2w-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-check" {...props}></Icon>
