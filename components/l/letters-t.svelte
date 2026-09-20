<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mih9617if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mih9617if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-t" {...props}></Icon>
