<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akzk_xbgp.css';
import '../../css/l/lp8u00bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akzk_xbgp"/><path clip-rule="evenodd" class="lp8u00bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bicycling-round-bold" {...props}></Icon>
