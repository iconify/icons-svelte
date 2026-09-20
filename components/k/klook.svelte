<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_7tlh19e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_7tlh19e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:klook" {...props}></Icon>
