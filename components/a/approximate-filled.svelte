<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is1rkcbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is1rkcbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:approximate-filled" {...props}></Icon>
