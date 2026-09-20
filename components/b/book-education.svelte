<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9u-32baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9u-32baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-education" {...props}></Icon>
