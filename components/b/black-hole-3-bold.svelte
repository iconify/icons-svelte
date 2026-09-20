<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzg_r58ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzg_r58ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:black-hole-3-bold" {...props}></Icon>
