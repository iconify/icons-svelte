<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5o5j3omz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s5o5j3omz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:arrow-up-right" {...props}></Icon>
