<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auqzvzbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auqzvzbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:list-plus-filled" {...props}></Icon>
