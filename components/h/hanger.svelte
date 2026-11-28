<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga3xw3bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga3xw3bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hanger" {...props}></Icon>
