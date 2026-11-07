<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os7xz0mqz.css';
import '../../css/f/f3axzccsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="os7xz0mqz"/><path class="f3axzccsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-square-bold-duotone" {...props}></Icon>
