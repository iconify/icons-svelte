<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d70u6rznq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d70u6rznq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cookie-off" {...props}></Icon>
