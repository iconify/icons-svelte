<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwzc0c7sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="uwzc0c7sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:border-style" {...props}></Icon>
