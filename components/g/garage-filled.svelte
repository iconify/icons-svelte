<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnu-_5bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnu-_5bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:garage-filled" {...props}></Icon>
