<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djzvpbbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="djzvpbbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:face-with-tongue-out-in-circle" {...props}></Icon>
