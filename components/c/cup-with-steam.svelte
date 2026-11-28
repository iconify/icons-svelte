<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-g8-zfkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j-g8-zfkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cup-with-steam" {...props}></Icon>
