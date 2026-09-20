<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiijosb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iiijosb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-speaking-to-amphitheater" {...props}></Icon>
