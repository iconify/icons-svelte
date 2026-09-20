<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cncj86rwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cncj86rwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-education-outline" {...props}></Icon>
