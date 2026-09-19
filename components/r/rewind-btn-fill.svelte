<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arq6blbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="arq6blbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:rewind-btn-fill" {...props}></Icon>
