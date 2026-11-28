<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1_ht_bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1_ht_bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flame-solid" {...props}></Icon>
