<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi5ik7blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hi5ik7blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:arrow" {...props}></Icon>
