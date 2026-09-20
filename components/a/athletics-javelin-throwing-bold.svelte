<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3num9tcq.css';
import '../../css/o/o3qegkbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3num9tcq"/><path class="o3qegkbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:athletics-javelin-throwing-bold" {...props}></Icon>
