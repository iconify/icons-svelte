<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd8e70owp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8e70owp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:add-circle-half-dot" {...props}></Icon>
