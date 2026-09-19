<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uynwg_bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uynwg_bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:dice-4" {...props}></Icon>
