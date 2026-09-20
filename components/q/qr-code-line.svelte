<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-39s1r3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-39s1r3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:qr-code-line" {...props}></Icon>
