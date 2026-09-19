<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce32om2az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce32om2az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:filter-mail-remove" {...props}></Icon>
