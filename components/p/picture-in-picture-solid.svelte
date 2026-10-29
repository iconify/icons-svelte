<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjrjh7x3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjrjh7x3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:picture-in-picture-solid" {...props}></Icon>
