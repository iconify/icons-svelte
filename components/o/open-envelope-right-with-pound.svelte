<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkhr1kw2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qkhr1kw2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-envelope-right-with-pound" {...props}></Icon>
