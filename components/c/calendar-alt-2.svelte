<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdsqszb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdsqszb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-alt-2" {...props}></Icon>
