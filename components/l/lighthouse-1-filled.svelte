<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwx86bcnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwx86bcnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lighthouse-1-filled" {...props}></Icon>
