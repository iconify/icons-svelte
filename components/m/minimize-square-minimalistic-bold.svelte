<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdadk5ibk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdadk5ibk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-square-minimalistic-bold" {...props}></Icon>
