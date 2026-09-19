<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuvcv35gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fuvcv35gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:queue-list-16-solid" {...props}></Icon>
