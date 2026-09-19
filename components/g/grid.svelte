<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8w016b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h8w016b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:grid" {...props}></Icon>
