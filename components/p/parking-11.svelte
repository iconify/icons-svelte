<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1lv9tb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="b1lv9tb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:parking-11" {...props}></Icon>
