<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd4od4bcx.css';
import '../../css/t/tm3vgc7aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd4od4bcx"/><path clip-rule="evenodd" class="tm3vgc7aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-down-light" {...props}></Icon>
