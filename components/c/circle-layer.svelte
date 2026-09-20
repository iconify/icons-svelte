<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz7sr6bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz7sr6bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:circle-layer" {...props}></Icon>
