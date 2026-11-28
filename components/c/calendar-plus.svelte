<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leze99baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leze99baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-plus" {...props}></Icon>
