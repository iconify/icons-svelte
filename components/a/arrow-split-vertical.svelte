<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-knu7bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-knu7bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-split-vertical" {...props}></Icon>
