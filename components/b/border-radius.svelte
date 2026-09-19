<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efff6o-je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efff6o-je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:border-radius" {...props}></Icon>
