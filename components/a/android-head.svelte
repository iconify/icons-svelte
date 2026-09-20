<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj2n_6b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj2n_6b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:android-head" {...props}></Icon>
