<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-357n8kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-357n8kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:popcorn-solid" {...props}></Icon>
