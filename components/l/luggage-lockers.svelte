<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toy3fsb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toy3fsb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:luggage-lockers" {...props}></Icon>
