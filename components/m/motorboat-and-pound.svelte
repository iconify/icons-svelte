<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dafof6oau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dafof6oau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-pound" {...props}></Icon>
