<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b26n3db1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b26n3db1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:angry-face" {...props}></Icon>
