<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az73ylb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az73ylb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:long-down" {...props}></Icon>
