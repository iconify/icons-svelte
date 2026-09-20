<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4850jj9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f4850jj9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nevada" {...props}></Icon>
