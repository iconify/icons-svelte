<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2h3c5b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2h3c5b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-rain" {...props}></Icon>
