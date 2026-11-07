<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n15g2dykh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n15g2dykh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-shake-outline" {...props}></Icon>
