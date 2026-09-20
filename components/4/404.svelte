<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hph7rtbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hph7rtbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:404" {...props}></Icon>
