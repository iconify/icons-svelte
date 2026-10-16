<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j71d__mgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":283.46,"height":283.46};
const content = `<path class="j71d__mgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:photoprism-light" {...props}></Icon>
