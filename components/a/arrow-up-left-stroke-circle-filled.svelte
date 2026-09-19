<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4_b4bczb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4_b4bczb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-left-stroke-circle-filled" {...props}></Icon>
