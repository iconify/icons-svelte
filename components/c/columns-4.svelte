<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx1bxabzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx1bxabzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:columns-4" {...props}></Icon>
