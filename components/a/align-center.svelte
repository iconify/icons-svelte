<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au37i9bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="au37i9bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:align-center" {...props}></Icon>
