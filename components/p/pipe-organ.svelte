<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oms87jhuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oms87jhuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pipe-organ" {...props}></Icon>
