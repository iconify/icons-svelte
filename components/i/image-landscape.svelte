<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3vra2bpp.css';
import '../../css/k/k80k31tai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3vra2bpp"/><path class="k80k31tai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-landscape" {...props}></Icon>
