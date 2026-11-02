<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkfbexgmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkfbexgmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:divide-line" {...props}></Icon>
