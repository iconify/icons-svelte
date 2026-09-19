<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv9rlsbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cv9rlsbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hockeyapp" {...props}></Icon>
