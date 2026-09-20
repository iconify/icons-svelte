<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xykb5e5ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xykb5e5ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cpu" {...props}></Icon>
