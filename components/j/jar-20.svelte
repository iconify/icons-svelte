<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpf2n7b-t.css';
import '../../css/v/vltu6acye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jpf2n7b-t"/><path class="vltu6acye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jar-20" {...props}></Icon>
