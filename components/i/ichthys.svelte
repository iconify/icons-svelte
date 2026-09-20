<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwqjbqb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iwqjbqb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ichthys" {...props}></Icon>
