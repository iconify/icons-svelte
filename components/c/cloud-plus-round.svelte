<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbwo-2beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbwo-2beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-plus-round" {...props}></Icon>
