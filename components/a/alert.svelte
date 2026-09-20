<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulydlxb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ulydlxb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:alert" {...props}></Icon>
