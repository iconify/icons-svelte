<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpmxxmerl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpmxxmerl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-bolt2" {...props}></Icon>
