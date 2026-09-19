<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aotbj3bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aotbj3bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:line-graph" {...props}></Icon>
