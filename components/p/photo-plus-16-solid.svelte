<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3wv0kwij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t3wv0kwij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-plus-16-solid" {...props}></Icon>
