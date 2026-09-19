<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc08l--tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dc08l--tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:question-octagon-fill" {...props}></Icon>
