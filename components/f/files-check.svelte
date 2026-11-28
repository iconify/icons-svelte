<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfj1x259w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfj1x259w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:files-check" {...props}></Icon>
