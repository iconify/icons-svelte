<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu400dbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eu400dbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-left-square" {...props}></Icon>
