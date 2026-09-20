<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2-__abmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2-__abmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil-add" {...props}></Icon>
