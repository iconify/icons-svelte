<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv74wh8fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv74wh8fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:paintbrush-2" {...props}></Icon>
