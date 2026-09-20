<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgzi01biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgzi01biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-star" {...props}></Icon>
