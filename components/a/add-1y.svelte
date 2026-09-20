<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv22kw38n.css';
import '../../css/m/mo7-9cc3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="kv22kw38n"/><path class="mo7-9cc3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:add-1y" {...props}></Icon>
