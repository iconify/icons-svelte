<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhvw9chnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhvw9chnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:option" {...props}></Icon>
