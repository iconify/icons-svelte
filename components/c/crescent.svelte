<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3258acki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j3258acki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crescent" {...props}></Icon>
