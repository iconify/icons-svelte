<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2nv_9ulb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2nv_9ulb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:grid-plus" {...props}></Icon>
