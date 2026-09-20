<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vor1jkb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vor1jkb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-pointer-down" {...props}></Icon>
