<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbm4d9pym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nbm4d9pym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-under-paragraph" {...props}></Icon>
