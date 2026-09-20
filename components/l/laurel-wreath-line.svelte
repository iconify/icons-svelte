<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s42hsbdah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s42hsbdah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laurel-wreath-line" {...props}></Icon>
