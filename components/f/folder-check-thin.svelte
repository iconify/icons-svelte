<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b918jacqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b918jacqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:folder-check-thin" {...props}></Icon>
