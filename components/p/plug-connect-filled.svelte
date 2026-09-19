<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7h9zxncv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7h9zxncv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plug-connect-filled" {...props}></Icon>
