<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzsz1rwsm.css';
import '../../css/g/ggufc0siv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pzsz1rwsm"/><path class="ggufc0siv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-minimalistic-bold" {...props}></Icon>
