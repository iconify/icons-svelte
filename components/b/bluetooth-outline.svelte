<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngywqob2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ngywqob2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:bluetooth-outline" {...props}></Icon>
