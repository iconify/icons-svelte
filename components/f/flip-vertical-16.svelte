<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukw-q400c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ukw-q400c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:flip-vertical-16" {...props}></Icon>
