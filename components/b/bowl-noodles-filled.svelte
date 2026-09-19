<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8d1k1s8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8d1k1s8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowl-noodles-filled" {...props}></Icon>
