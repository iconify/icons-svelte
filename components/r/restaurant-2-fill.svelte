<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqvjw5zyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqvjw5zyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:restaurant-2-fill" {...props}></Icon>
