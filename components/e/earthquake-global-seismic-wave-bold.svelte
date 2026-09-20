<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcm739wxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pcm739wxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:earthquake-global-seismic-wave-bold" {...props}></Icon>
