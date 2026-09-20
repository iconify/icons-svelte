<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygh_68bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygh_68bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-fold-2-line" {...props}></Icon>
