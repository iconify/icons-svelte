<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4_m7ebys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4_m7ebys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:key-line" {...props}></Icon>
