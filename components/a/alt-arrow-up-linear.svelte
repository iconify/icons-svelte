<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbroeosox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbroeosox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-up-linear" {...props}></Icon>
