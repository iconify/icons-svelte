<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m05bd9i9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m05bd9i9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:game-structure" {...props}></Icon>
