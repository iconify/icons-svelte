<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb5vreb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pb5vreb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone4-filled" {...props}></Icon>
