<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x77m4fblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x77m4fblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:copyright" {...props}></Icon>
