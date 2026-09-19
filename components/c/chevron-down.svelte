<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukp6v6bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ukp6v6bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chevron-down" {...props}></Icon>
