<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbapbibwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbapbibwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cookie" {...props}></Icon>
