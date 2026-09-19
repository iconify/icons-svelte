<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n01ij7bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":640};
const content = `<path class="n01ij7bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:chevronup" {...props}></Icon>
