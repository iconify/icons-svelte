<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eers39bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eers39bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:angle" {...props}></Icon>
