<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlymt9bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hlymt9bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crosswalk-markings-lines" {...props}></Icon>
