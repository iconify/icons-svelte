<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6jg8lhed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6jg8lhed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-party" {...props}></Icon>
