<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2e5gzblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="d2e5gzblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:knight" {...props}></Icon>
