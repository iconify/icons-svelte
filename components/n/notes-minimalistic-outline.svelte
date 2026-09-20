<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv0tzjduf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bv0tzjduf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notes-minimalistic-outline" {...props}></Icon>
