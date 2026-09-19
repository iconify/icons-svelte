<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/davv_jkhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="davv_jkhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:list-order" {...props}></Icon>
