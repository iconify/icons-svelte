<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw0pllb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sw0pllb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-left-bold" {...props}></Icon>
