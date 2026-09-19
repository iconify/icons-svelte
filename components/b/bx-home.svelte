<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3gt7xbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3gt7xbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-home" {...props}></Icon>
