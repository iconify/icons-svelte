<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r867uzbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r867uzbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:question-16" {...props}></Icon>
