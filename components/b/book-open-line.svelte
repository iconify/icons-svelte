<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkzwb8bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkzwb8bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-open-line" {...props}></Icon>
