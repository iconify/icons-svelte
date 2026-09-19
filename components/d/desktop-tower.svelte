<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta82op5ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta82op5ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:desktop-tower" {...props}></Icon>
