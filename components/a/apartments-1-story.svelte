<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acvxodb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="acvxodb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-1-story" {...props}></Icon>
