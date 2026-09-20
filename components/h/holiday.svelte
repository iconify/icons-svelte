<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg1fkgbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg1fkgbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:holiday" {...props}></Icon>
