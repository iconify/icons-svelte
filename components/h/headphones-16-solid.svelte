<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej9hctbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ej9hctbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headphones-16-solid" {...props}></Icon>
