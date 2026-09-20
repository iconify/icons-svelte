<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdijvhc5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fdijvhc5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:flag-16" {...props}></Icon>
