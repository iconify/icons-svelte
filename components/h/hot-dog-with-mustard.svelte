<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u02ts_bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u02ts_bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hot-dog-with-mustard" {...props}></Icon>
