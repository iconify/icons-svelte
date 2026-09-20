<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9ax2lb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ax2lb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-3-line" {...props}></Icon>
