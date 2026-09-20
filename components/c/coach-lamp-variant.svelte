<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlp52tbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlp52tbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coach-lamp-variant" {...props}></Icon>
