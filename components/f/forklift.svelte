<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/val3pabiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="val3pabiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:forklift" {...props}></Icon>
