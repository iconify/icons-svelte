<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-n83abfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b-n83abfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-code-fill" {...props}></Icon>
