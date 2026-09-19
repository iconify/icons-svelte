<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7p4sbcuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="j7p4sbcuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:geo" {...props}></Icon>
