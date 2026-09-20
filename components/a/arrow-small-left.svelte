<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubn55kbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6,"height":16};
const content = `<path class="ubn55kbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-small-left" {...props}></Icon>
