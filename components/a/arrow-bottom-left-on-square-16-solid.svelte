<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0adcrzki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a0adcrzki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-bottom-left-on-square-16-solid" {...props}></Icon>
