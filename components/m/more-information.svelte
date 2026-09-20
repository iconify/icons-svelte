<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmw69mb4r.css';
import '../../css/w/w4c3hmsue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="dmw69mb4r"/><path class="w4c3hmsue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:more-information" {...props}></Icon>
