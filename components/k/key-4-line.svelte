<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qki58hbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qki58hbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-4-line" {...props}></Icon>
