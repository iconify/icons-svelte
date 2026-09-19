<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksbqztbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksbqztbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevron-right-square" {...props}></Icon>
