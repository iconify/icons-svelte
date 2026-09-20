<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kztwflb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="kztwflb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:close" {...props}></Icon>
