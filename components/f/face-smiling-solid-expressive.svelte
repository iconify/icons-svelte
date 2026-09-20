<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxct1bw3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxct1bw3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:face-smiling-solid-expressive" {...props}></Icon>
