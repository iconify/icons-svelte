<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-thqdb7y.css';
import '../../css/w/w-335_d0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-thqdb7y"/><path class="w-335_d0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:camera" {...props}></Icon>
