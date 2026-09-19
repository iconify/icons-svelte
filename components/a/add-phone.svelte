<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0y3bjbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b0y3bjbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:add-phone" {...props}></Icon>
