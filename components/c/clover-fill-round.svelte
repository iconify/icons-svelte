<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vapdjacjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vapdjacjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clover-fill-round" {...props}></Icon>
