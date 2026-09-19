<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juyn0yznl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juyn0yznl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dumbbell-03" {...props}></Icon>
