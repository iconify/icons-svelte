<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvq_hx_ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nvq_hx_ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-light" {...props}></Icon>
