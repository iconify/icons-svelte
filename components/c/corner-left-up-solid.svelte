<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c725z4k7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c725z4k7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-left-up-solid" {...props}></Icon>
