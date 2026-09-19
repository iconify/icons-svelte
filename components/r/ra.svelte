<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9spjjbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="j9spjjbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:ra" {...props}></Icon>
