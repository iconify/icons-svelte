<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq5omkbde.css';
import '../../css/u/u4crvcq6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq5omkbde"/><path class="u4crvcq6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pin-duotone-line" {...props}></Icon>
