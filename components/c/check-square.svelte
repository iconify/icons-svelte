<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kixt_hbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kixt_hbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:check-square" {...props}></Icon>
