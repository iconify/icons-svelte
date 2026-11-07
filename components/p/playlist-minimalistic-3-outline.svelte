<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcu_ujjgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lcu_ujjgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-minimalistic-3-outline" {...props}></Icon>
