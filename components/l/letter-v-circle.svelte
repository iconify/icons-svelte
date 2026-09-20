<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1lmm6bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1lmm6bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-v-circle" {...props}></Icon>
