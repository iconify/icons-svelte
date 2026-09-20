<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jerx1q9ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jerx1q9ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:explicit-bold" {...props}></Icon>
