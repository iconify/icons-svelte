<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b389uu97b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b389uu97b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:passport-with-netherlands" {...props}></Icon>
