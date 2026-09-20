<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/difr24bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="difr24bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-fold-line" {...props}></Icon>
