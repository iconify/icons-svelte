<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8bze1aed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8bze1aed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hard-drive" {...props}></Icon>
