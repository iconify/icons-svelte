<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfk76sblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfk76sblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:apple-2" {...props}></Icon>
