<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpy0vg23g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpy0vg23g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:alarm-off" {...props}></Icon>
