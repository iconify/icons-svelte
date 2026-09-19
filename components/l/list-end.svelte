<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo1qhftup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo1qhftup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:list-end" {...props}></Icon>
