<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfqbdib-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfqbdib-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-subdirectory-left" {...props}></Icon>
