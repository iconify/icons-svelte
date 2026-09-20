<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k48fiacvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k48fiacvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:helium-mobile-dark" {...props}></Icon>
