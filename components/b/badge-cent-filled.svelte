<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0oed5ccq.css';
import '../../css/m/mkm-s0byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0oed5ccq"/><path clip-rule="evenodd" class="mkm-s0byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-cent-filled" {...props}></Icon>
