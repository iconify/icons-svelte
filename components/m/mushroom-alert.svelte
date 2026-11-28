<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-ve-3bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-ve-3bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mushroom-alert" {...props}></Icon>
