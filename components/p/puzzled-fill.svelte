<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8p995ben.css';
import '../../css/h/hpnmk0bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i8p995ben"/><path class="hpnmk0bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:puzzled-fill" {...props}></Icon>
