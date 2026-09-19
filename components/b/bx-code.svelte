<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw477rt8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw477rt8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-code" {...props}></Icon>
