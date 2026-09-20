<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3ggscbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3ggscbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pimjo-symbol" {...props}></Icon>
