<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyg-96bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eyg-96bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pin-16-solid" {...props}></Icon>
