<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpx9cthdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpx9cthdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-heart" {...props}></Icon>
