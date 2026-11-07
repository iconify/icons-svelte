<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_51kh_lz.css';
import '../../css/i/i6wfjybuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_51kh_lz"/><path class="i6wfjybuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:body-bold-duotone" {...props}></Icon>
