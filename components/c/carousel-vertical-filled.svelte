<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9mopgb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9mopgb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:carousel-vertical-filled" {...props}></Icon>
