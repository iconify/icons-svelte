<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb0sabbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb0sabbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-sort-z-a" {...props}></Icon>
